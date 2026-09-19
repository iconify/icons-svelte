<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhse-g5zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fhse-g5zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-center-stroke-16" {...props}></Icon>
