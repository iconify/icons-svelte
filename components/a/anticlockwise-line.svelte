<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr0zv381u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr0zv381u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anticlockwise-line" {...props}></Icon>
