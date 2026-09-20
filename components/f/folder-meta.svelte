<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5evchskr.css';
import '../../css/n/ns67zpbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a5evchskr"/><path class="ns67zpbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-meta" {...props}></Icon>
