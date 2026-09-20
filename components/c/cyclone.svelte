<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh0pj9b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wh0pj9b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:cyclone" {...props}></Icon>
