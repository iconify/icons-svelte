<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmb9zzosy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":65,"left":33};
const content = `<path class="dmb9zzosy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chunk-light" {...props}></Icon>
