<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yisex-bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yisex-bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-reverse-camera" {...props}></Icon>
