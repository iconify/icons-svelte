<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktz2u4-vt.css';
import '../../css/y/y72en9ydc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ktz2u4-vt"/><path class="y72en9ydc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-light-bulb" {...props}></Icon>
