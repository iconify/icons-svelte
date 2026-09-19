<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxix6l8rl.css';
import '../../css/h/hy4ycj-aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cxix6l8rl"/><path class="hy4ycj-aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:charging-station" {...props}></Icon>
