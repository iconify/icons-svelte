<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8qoe7bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d8qoe7bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-spreadsheet-fill-16" {...props}></Icon>
