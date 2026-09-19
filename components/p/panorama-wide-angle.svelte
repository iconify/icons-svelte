<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi_in7rna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="fi_in7rna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:panorama-wide-angle" {...props}></Icon>
