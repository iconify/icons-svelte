<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dycx40bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2176,"height":1664};
const content = `<path class="dycx40bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:cow" {...props}></Icon>
