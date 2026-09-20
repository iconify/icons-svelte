<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzpozeuvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qzpozeuvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-down-2" {...props}></Icon>
