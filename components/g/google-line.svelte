<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuilsm50n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yuilsm50n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:google-line" {...props}></Icon>
