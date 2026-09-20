<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbr5r4bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fbr5r4bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-submariner-dark" {...props}></Icon>
