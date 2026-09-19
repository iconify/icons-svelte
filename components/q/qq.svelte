<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9fy51bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s9fy51bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:qq" {...props}></Icon>
