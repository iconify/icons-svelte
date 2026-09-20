<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyofjvw_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eyofjvw_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:cocktail-glass" {...props}></Icon>
