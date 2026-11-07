<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g65hvpbwb.css';
import '../../css/t/t7fjfmboq.css';
import '../../css/z/zgg5gabcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g65hvpbwb"/><path class="t7fjfmboq"/><path class="zgg5gabcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:moon-stars-bold" {...props}></Icon>
