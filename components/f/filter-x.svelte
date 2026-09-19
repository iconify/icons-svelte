<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-9kwzbci.css';
import '../../css/l/lh4n09blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y-9kwzbci"/><path class="lh4n09blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:filter-x" {...props}></Icon>
