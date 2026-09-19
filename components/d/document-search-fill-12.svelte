<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7ku-vbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="o7ku-vbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:document-search-fill-12" {...props}></Icon>
