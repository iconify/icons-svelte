<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npopgqbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="npopgqbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hexagon-outline" {...props}></Icon>
