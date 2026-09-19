<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzgf6_ocr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zzgf6_ocr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:overmind" {...props}></Icon>
