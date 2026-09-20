<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug_ngt74t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ug_ngt74t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:elevator" {...props}></Icon>
