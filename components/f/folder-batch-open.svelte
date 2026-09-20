<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yasv75-0z.css';
import '../../css/l/lommj4luf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yasv75-0z"/><path class="lommj4luf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-batch-open" {...props}></Icon>
