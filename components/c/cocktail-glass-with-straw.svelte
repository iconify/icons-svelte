<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb-9tyb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mb-9tyb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:cocktail-glass-with-straw" {...props}></Icon>
