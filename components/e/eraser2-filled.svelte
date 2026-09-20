<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgxm9rbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgxm9rbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:eraser2-filled" {...props}></Icon>
