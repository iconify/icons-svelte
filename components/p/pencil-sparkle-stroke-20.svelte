<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul0vswbpp.css';
import '../../css/q/qggpi_b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ul0vswbpp"/><path class="qggpi_b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pencil-sparkle-stroke-20" {...props}></Icon>
