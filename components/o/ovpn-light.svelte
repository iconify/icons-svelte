<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkv94nbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nkv94nbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ovpn-light" {...props}></Icon>
