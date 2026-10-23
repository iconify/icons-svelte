<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt1q0qbdx.css';
import '../../css/y/yq70e9tim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt1q0qbdx"/><path clip-rule="evenodd" class="yq70e9tim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cpu-ai-filled" {...props}></Icon>
