<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hms937aej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hms937aej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:happy-face" {...props}></Icon>
