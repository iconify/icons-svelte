<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae56v0u4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ae56v0u4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ovpn-dark" {...props}></Icon>
