<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs1keu_xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fs1keu_xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:artist" {...props}></Icon>
