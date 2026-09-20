<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrxpgubkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":272.7,"height":238.5};
const content = `<path class="nrxpgubkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mcdonalds" {...props}></Icon>
