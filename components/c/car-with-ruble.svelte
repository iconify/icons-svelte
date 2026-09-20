<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgsqbac3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fgsqbac3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-with-ruble" {...props}></Icon>
