<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rve_w0bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rve_w0bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:funnel-plus-fill" {...props}></Icon>
