<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxfc_g7ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxfc_g7ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-3-line" {...props}></Icon>
