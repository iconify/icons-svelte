<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruh8bqbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ruh8bqbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-with-hiking-pole-wearing-backpack-under-gabled-roof" {...props}></Icon>
