<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5549tbpb.css';
import '../../css/z/zr90yfbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d5549tbpb"/><path class="zr90yfbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:connectwise-screenconnect-light" {...props}></Icon>
