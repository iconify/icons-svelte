<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tstc3xbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tstc3xbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:fitocracy" {...props}></Icon>
