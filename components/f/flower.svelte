<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdi43l57p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":480};
const content = `<path class="vdi43l57p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:flower" {...props}></Icon>
