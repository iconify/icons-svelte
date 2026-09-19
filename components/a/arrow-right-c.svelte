<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1j2x1sim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k1j2x1sim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-right-c" {...props}></Icon>
