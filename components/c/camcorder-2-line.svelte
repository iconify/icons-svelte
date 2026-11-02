<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev_cvrjhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev_cvrjhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-2-line" {...props}></Icon>
