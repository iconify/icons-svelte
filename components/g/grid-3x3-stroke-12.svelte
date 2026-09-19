<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5exsidjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y5exsidjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:grid-3x3-stroke-12" {...props}></Icon>
