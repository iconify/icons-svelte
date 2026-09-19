<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpt8g1b7z.css';
import '../../css/n/nketkfbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wpt8g1b7z"/><path class="nketkfbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-video" {...props}></Icon>
