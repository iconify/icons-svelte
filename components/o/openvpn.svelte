<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q84_d0bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q84_d0bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:openvpn" {...props}></Icon>
