<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu-w0ybfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu-w0ybfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:elevator" {...props}></Icon>
