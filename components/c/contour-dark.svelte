<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7g5w-bhc.css';
import '../../css/q/qu_-3cc-k.css';
import '../../css/u/urw0m8b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":360,"height":360};
const content = `<path class="i7g5w-bhc"/><path class="qu_-3cc-k"/><path class="urw0m8b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:contour-dark" {...props}></Icon>
