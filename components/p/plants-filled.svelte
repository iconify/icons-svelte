<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx_m0xbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xx_m0xbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plants-filled" {...props}></Icon>
