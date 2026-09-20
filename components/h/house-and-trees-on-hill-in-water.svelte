<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnj3ggbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jnj3ggbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:house-and-trees-on-hill-in-water" {...props}></Icon>
