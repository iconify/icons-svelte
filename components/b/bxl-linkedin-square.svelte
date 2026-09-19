<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hik8q7bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hik8q7bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-linkedin-square" {...props}></Icon>
