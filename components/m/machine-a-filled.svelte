<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqou_g3dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="oqou_g3dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:machine-a-filled" {...props}></Icon>
