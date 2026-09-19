<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv4grma8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv4grma8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-visual-studio" {...props}></Icon>
