<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij5gh3byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<path class="ij5gh3byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kraken-dark" {...props}></Icon>
