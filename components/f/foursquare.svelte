<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz0j6tbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":961};
const content = `<path class="iz0j6tbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:foursquare" {...props}></Icon>
