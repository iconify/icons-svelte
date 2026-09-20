<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-vf2vbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c-vf2vbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:recycle" {...props}></Icon>
