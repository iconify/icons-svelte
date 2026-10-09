<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qypcfebhs.css';
import '../../css/e/e8j_nwbgk.css';
import '../../css/b/by5qfxf8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qypcfebhs"/><path class="e8j_nwbgk"/><path class="by5qfxf8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:garage-20" {...props}></Icon>
