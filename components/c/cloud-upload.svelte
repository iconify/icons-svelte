<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubi-4pbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ubi-4pbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cloud-upload" {...props}></Icon>
