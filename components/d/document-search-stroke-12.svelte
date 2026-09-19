<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6hh1sbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="x6hh1sbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:document-search-stroke-12" {...props}></Icon>
