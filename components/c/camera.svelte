<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke8sr7biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ke8sr7biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:camera" {...props}></Icon>
