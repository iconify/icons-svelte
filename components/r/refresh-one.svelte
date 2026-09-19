<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/i/i7iloobad.css';
import '../../css/r/r-mrtlb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><rect transform="rotate(-45 17 24.071)" class="i7iloobad"/><path class="r-mrtlb8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:refresh-one" {...props}></Icon>
