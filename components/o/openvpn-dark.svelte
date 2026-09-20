<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buqa66bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="buqa66bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openvpn-dark" {...props}></Icon>
