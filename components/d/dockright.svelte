<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl6wf-b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sl6wf-b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:dockright" {...props}></Icon>
