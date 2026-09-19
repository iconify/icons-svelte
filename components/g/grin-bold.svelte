<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wchwsk_5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wchwsk_5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grin-bold" {...props}></Icon>
