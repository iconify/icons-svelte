<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv2wyhb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wv2wyhb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:digital-totem-with-info-i" {...props}></Icon>
