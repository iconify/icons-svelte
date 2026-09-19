<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-y7l7lfv.css';
import '../../css/x/xtad_yvwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p-y7l7lfv"/><path class="xtad_yvwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-registry" {...props}></Icon>
