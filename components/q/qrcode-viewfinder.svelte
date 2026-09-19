<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3bss3zbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d3bss3zbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:qrcode-viewfinder" {...props}></Icon>
