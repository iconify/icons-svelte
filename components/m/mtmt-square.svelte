<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzkdiqb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="uzkdiqb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:mtmt-square" {...props}></Icon>
