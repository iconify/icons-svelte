<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgj5w-y0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qgj5w-y0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:flash-3-flat" {...props}></Icon>
