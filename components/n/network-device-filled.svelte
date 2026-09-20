<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk8njw3yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hk8njw3yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:network-device-filled" {...props}></Icon>
