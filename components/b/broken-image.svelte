<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no54uea3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="no54uea3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:broken-image" {...props}></Icon>
