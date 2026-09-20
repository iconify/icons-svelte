<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocvy942nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ocvy942nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickup-truck-under-list-beside-checkmark" {...props}></Icon>
