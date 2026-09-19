<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inr8_8btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="inr8_8btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:binoculars" {...props}></Icon>
