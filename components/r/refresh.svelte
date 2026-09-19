<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujmo2hbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ujmo2hbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:refresh" {...props}></Icon>
