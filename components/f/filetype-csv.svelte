<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gom3s0blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gom3s0blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-csv" {...props}></Icon>
