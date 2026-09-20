<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctfz9yp6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ctfz9yp6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lattice-tower-with-observation-deck-on-ground" {...props}></Icon>
