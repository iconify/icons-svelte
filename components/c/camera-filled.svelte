<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxjypom5p.css';
import '../../css/h/h_yj_ybgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxjypom5p"/><path clip-rule="evenodd" class="h_yj_ybgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:camera-filled" {...props}></Icon>
