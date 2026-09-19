<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9z3ehbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p9z3ehbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:bed" {...props}></Icon>
