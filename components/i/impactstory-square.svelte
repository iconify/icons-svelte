<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_m8x9bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="x_m8x9bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:impactstory-square" {...props}></Icon>
