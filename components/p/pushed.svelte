<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqcmo_wwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xqcmo_wwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pushed" {...props}></Icon>
