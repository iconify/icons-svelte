<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfoz3-mbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kfoz3-mbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fish-head-beside-barbed-hook-under-paragraph" {...props}></Icon>
