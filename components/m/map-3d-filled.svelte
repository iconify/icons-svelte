<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ron-o7_wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ron-o7_wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-3d-filled" {...props}></Icon>
