<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uehp1-aij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<path class="uehp1-aij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:metube" {...props}></Icon>
