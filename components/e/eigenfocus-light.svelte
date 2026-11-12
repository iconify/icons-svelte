<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1th6cc6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t1th6cc6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eigenfocus-light" {...props}></Icon>
