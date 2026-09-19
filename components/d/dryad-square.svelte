<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-hvr0byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="d-hvr0byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:dryad-square" {...props}></Icon>
