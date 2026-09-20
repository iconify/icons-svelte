<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od-1d7bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="od-1d7bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proxcenter-dark" {...props}></Icon>
