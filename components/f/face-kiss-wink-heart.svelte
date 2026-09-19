<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dja5gvbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dja5gvbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-kiss-wink-heart" {...props}></Icon>
