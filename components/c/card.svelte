<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjlr4l5vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjlr4l5vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:card" {...props}></Icon>
