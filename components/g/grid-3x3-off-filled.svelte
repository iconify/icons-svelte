<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj9l6dm3r.css';
import '../../css/g/gxvh0c--h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj9l6dm3r"/><path class="gxvh0c--h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:grid-3x3-off-filled" {...props}></Icon>
