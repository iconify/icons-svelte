<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2htkmh4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2htkmh4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:airplane-line" {...props}></Icon>
