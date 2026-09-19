<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8n_0x-qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w8n_0x-qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bullet-list" {...props}></Icon>
