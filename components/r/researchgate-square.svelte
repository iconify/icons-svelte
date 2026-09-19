<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhhtn6bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="jhhtn6bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:researchgate-square" {...props}></Icon>
