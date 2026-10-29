<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7o7bfbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7o7bfbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-owl-solid" {...props}></Icon>
