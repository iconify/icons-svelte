<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alk5rr8yk.css';
import '../../css/p/pwnej6bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="alk5rr8yk"/><path class="pwnej6bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:icicles-48-bold" {...props}></Icon>
