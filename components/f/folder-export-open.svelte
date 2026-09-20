<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb8w2y-mu.css';
import '../../css/n/nra3bcbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sb8w2y-mu"/><path class="nra3bcbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-export-open" {...props}></Icon>
