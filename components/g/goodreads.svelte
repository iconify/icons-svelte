<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb5n4phcw.css';
import '../../css/d/dggo-4bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yb5n4phcw"/><path class="dggo-4bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:goodreads" {...props}></Icon>
