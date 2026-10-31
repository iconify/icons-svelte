<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8r1fcc5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8r1fcc5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-search-gloss" {...props}></Icon>
