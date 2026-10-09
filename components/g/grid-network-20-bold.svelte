<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b68x9qh8q.css';
import '../../css/w/w80_ihp8f.css';
import '../../css/k/k7gdhlbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b68x9qh8q"/><path class="w80_ihp8f"/><path class="k7gdhlbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-network-20-bold" {...props}></Icon>
