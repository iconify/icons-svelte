<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcik8bwgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vcik8bwgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:olive-light" {...props}></Icon>
