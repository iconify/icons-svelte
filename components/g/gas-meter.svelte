<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpvwby7ij.css';
import '../../css/o/oos9gs_0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lpvwby7ij"/><path class="oos9gs_0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:gas-meter" {...props}></Icon>
