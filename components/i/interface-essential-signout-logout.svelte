<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofc2p7fff.css';
import '../../css/o/o2idt1eal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ofc2p7fff"/><path class="o2idt1eal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-signout-logout" {...props}></Icon>
