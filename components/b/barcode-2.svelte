<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgm26p3ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgm26p3ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:barcode-2" {...props}></Icon>
