<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr3r1xpmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yr3r1xpmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-spreadsheet" {...props}></Icon>
