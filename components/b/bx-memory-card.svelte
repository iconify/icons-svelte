<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pij_c5y_o.css';
import '../../css/g/g6bv-gb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pij_c5y_o"/><path class="g6bv-gb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-memory-card" {...props}></Icon>
