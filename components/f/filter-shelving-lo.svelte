<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0pbf3b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c0pbf3b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:filter-shelving-lo" {...props}></Icon>
