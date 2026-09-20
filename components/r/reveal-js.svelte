<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddkf61byi.css';
import '../../css/s/s45cdxblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ddkf61byi"/><path class="s45cdxblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reveal-js" {...props}></Icon>
