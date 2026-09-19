<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxgl8sb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cxgl8sb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:dribbble-square" {...props}></Icon>
