<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnzp6-gsx.css';
import '../../css/w/wl3st4cag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pnzp6-gsx"/><path clip-rule="evenodd" class="wl3st4cag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:chevron-double-up-16" {...props}></Icon>
