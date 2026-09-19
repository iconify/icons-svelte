<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvk1p8bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":896};
const content = `<path class="rvk1p8bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:addfolderalt" {...props}></Icon>
