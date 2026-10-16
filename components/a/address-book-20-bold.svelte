<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2linuthc.css';
import '../../css/p/p4elc_bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p2linuthc"/><path class="p4elc_bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:address-book-20-bold" {...props}></Icon>
