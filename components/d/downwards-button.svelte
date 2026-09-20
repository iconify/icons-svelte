<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiwicdcdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jiwicdcdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:downwards-button" {...props}></Icon>
