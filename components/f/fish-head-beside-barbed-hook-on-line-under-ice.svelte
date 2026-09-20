<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smgqmefax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="smgqmefax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fish-head-beside-barbed-hook-on-line-under-ice" {...props}></Icon>
