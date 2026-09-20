<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-4zo-uap.css';
import '../../css/a/aoxojqb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w-4zo-uap"/><path class="aoxojqb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-delta-open" {...props}></Icon>
