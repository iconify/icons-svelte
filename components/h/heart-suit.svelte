<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uroqbab3z.css';
import '../../css/d/d23743b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="uroqbab3z"/><path class="d23743b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:heart-suit" {...props}></Icon>
