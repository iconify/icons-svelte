<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvzkb_bhc.css';
import '../../css/r/rhvegq0-t.css';
import '../../css/i/i0x2txbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hvzkb_bhc"/><path class="rhvegq0-t"/><path class="i0x2txbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-search-20-bold" {...props}></Icon>
