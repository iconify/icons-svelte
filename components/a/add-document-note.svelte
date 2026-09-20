<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu_lq32wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tu_lq32wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:add-document-note" {...props}></Icon>
