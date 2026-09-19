<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xucuw-bde.css';
import '../../css/y/y8gwbgbko.css';
import '../../css/n/nu3mrp6zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xucuw-bde"/><path class="y8gwbgbko"/><path class="nu3mrp6zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:nose" {...props}></Icon>
