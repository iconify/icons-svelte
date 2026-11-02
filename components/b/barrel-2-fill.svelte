<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p08234b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p08234b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:barrel-2-fill" {...props}></Icon>
