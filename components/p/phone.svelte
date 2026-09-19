<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksn07eq4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ksn07eq4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:phone" {...props}></Icon>
