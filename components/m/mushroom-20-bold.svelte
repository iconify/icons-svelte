<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv6j1_b0y.css';
import '../../css/i/i2kxrqbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hv6j1_b0y"/><path class="i2kxrqbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mushroom-20-bold" {...props}></Icon>
