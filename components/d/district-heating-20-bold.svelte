<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij_yecsrd.css';
import '../../css/i/ihj0a5_zp.css';
import '../../css/r/r8m749-bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ij_yecsrd"/><path class="ihj0a5_zp"/><path class="r8m749-bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:district-heating-20-bold" {...props}></Icon>
