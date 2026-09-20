<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h070l8jto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h070l8jto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:lady" {...props}></Icon>
