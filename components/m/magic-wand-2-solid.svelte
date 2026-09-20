<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuksv_b7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vuksv_b7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:magic-wand-2-solid" {...props}></Icon>
