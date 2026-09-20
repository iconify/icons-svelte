<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pffnfbbjn.css';
import '../../css/n/nr5mntn4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pffnfbbjn"/><path class="nr5mntn4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-drizzle-open" {...props}></Icon>
