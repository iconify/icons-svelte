<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmbmp5byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fmbmp5byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:equal-20-bold" {...props}></Icon>
