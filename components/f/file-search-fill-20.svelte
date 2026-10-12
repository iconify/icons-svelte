<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5nfh-t8z.css';
import '../../css/g/gzx0z1m6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w5nfh-t8z"/><path class="gzx0z1m6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-search-fill-20" {...props}></Icon>
