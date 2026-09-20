<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdt1j_b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pdt1j_b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:code" {...props}></Icon>
