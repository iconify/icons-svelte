<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrus5xbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yrus5xbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mega-dark" {...props}></Icon>
