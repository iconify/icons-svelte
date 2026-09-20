<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p21c9ubxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p21c9ubxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:pressure-high-alt" {...props}></Icon>
