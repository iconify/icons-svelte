<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pffnfbbjn.css';
import '../../css/g/gnnj1jfmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pffnfbbjn"/><path class="gnnj1jfmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-download-open" {...props}></Icon>
