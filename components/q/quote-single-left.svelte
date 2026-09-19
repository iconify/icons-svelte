<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn0ezyjmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn0ezyjmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:quote-single-left" {...props}></Icon>
