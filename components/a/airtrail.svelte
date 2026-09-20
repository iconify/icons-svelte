<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa036zbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pa036zbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:airtrail" {...props}></Icon>
