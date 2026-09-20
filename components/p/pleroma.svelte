<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdr_4acws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hdr_4acws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pleroma" {...props}></Icon>
