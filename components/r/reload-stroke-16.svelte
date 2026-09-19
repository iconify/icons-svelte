<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id4ivymod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="id4ivymod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:reload-stroke-16" {...props}></Icon>
