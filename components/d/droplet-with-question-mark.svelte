<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bchglacsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bchglacsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:droplet-with-question-mark" {...props}></Icon>
