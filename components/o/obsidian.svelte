<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt3uovblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lt3uovblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:obsidian" {...props}></Icon>
