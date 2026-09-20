<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx852xbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gx852xbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phoscon" {...props}></Icon>
