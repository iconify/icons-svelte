<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqydb2b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wqydb2b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-spreadsheet-stroke-16" {...props}></Icon>
