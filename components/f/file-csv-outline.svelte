<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbdew6bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vbdew6bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-csv-outline" {...props}></Icon>
