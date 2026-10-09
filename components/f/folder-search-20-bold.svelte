<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2ghl_lxl.css';
import '../../css/z/zb-g-abte.css';
import '../../css/i/i0x2txbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w2ghl_lxl"/><path class="zb-g-abte"/><path class="i0x2txbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-search-20-bold" {...props}></Icon>
