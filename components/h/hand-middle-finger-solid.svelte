<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf2bjwbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uf2bjwbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-middle-finger-solid" {...props}></Icon>
