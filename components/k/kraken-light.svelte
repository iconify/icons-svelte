<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oelcicc3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":150.5,"height":25.6};
const content = `<path class="oelcicc3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kraken-light" {...props}></Icon>
