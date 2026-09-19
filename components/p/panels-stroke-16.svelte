<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psh001bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="psh001bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:panels-stroke-16" {...props}></Icon>
