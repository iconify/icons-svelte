<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxg_-4wtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pxg_-4wtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:document-delete" {...props}></Icon>
