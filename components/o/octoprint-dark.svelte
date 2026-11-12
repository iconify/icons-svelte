<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrul9j3dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zrul9j3dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:octoprint-dark" {...props}></Icon>
