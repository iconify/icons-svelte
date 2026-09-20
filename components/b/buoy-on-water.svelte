<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nef45ubzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nef45ubzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:buoy-on-water" {...props}></Icon>
