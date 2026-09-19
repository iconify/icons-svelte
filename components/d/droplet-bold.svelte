<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3t59pb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="t3t59pb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:droplet-bold" {...props}></Icon>
