<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skzakomwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="skzakomwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:document-search-fill-16" {...props}></Icon>
