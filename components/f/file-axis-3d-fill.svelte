<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb_xsvb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hb_xsvb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-axis-3d-fill" {...props}></Icon>
