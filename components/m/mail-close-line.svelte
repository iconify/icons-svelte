<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m77e_vbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m77e_vbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-close-line" {...props}></Icon>
