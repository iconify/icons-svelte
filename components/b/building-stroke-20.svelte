<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grhpkv0pg.css';
import '../../css/f/fc-vduj0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="grhpkv0pg"/><path class="fc-vduj0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:building-stroke-20" {...props}></Icon>
