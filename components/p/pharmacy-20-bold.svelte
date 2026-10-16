<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4hf1bcaj.css';
import '../../css/b/b6bjo8bom.css';
import '../../css/a/ad_8r9xgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p4hf1bcaj"/><path class="b6bjo8bom"/><path class="ad_8r9xgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pharmacy-20-bold" {...props}></Icon>
