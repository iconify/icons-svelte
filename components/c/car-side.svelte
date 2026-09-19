<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt-nmm86o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="yt-nmm86o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:car-side" {...props}></Icon>
