<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whew0bbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="whew0bbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ovpn-dark" {...props}></Icon>
