<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nseg2ysar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nseg2ysar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:restreamer-light" {...props}></Icon>
