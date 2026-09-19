<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooot1hbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ooot1hbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:rhino3d" {...props}></Icon>
