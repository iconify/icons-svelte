<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wblo352dq.css';
import '../../css/a/afjkbrlmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b wblo352dq"/><path class="afjkbrlmd b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:clerk" {...props}></Icon>
