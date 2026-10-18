<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsom4l03p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsom4l03p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bath" {...props}></Icon>
