<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl_5e3bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl_5e3bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:expand-2" {...props}></Icon>
