<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cujrrqbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="cujrrqbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:dataverse-square" {...props}></Icon>
