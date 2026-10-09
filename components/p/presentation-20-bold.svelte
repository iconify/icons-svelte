<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_j6v7gna.css';
import '../../css/c/cbr70bcko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k_j6v7gna"/><path class="cbr70bcko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:presentation-20-bold" {...props}></Icon>
