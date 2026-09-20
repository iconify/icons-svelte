<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yveeyxb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yveeyxb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-up-line" {...props}></Icon>
