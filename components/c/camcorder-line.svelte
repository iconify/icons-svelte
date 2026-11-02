<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfh1gbcgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfh1gbcgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-line" {...props}></Icon>
