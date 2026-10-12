<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwwz45hpf.css';
import '../../css/v/v_rtg2u6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pwwz45hpf"/><path class="v_rtg2u6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pill-bottle-48" {...props}></Icon>
