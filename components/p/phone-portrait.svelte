<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e00fw2bit.css';
import '../../css/v/vz-n1gf_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><path id="SVG0BHc9coD" class="e00fw2bit"/></defs><use href="#SVG0BHc9coD"/><path class="vz-n1gf_b"/><use href="#SVG0BHc9coD"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:phone-portrait" {...props}></Icon>
