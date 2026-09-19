<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isz6hd-im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="isz6hd-im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:ciencia-vitae-square" {...props}></Icon>
