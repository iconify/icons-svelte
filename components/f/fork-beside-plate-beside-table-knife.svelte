<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4k1elb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u4k1elb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fork-beside-plate-beside-table-knife" {...props}></Icon>
