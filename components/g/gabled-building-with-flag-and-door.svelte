<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8oiug1hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s8oiug1hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gabled-building-with-flag-and-door" {...props}></Icon>
