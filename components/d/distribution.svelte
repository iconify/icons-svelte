<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3jglbcke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k3jglbcke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:distribution" {...props}></Icon>
