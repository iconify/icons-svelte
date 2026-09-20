<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpt9bf_hq.css';
import '../../css/f/f32uk7b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fpt9bf_hq"/><path class="f32uk7b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:glowing-star" {...props}></Icon>
