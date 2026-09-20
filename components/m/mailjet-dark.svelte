<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwy927bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rwy927bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailjet-dark" {...props}></Icon>
