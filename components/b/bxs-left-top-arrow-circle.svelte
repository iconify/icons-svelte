<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_m5s5bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_m5s5bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-left-top-arrow-circle" {...props}></Icon>
