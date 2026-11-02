<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys0i8gzui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys0i8gzui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airplane-fill" {...props}></Icon>
