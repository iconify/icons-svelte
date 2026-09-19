<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0sscpbxm.css';
import '../../css/t/toyc3i1pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0sscpbxm"/><path class="toyc3i1pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:camera-home-filled" {...props}></Icon>
