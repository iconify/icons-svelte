<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7vch6bck.css';
import '../../css/p/p8nic8bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c7vch6bck"/><path class="p8nic8bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openvpn" {...props}></Icon>
