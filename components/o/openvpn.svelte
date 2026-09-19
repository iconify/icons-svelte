<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5_icy2kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f5_icy2kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:openvpn" {...props}></Icon>
