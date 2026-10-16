<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6og01bov.css';
import '../../css/i/ijpeexi0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z6og01bov"/><path class="ijpeexi0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-price-20" {...props}></Icon>
