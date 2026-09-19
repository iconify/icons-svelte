<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfzqp5zje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfzqp5zje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-squarespace" {...props}></Icon>
