<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w973myp8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w973myp8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:multiplemusicalnotes" {...props}></Icon>
