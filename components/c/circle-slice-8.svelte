<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaji_jb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vaji_jb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:circle-slice-8" {...props}></Icon>
