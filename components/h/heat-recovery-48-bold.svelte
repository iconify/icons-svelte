<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzlanurfx.css';
import '../../css/x/x5igzyszp.css';
import '../../css/z/zwpgspbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dzlanurfx"/><path class="x5igzyszp"/><path class="zwpgspbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-recovery-48-bold" {...props}></Icon>
