<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh7ab-y9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":472};
const content = `<path class="sh7ab-y9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:power-setting" {...props}></Icon>
