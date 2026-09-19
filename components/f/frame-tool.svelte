<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydjiazbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydjiazbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:frame-tool" {...props}></Icon>
