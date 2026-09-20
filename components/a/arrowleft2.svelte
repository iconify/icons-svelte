<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzle8-bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nzle8-bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:arrowleft2" {...props}></Icon>
