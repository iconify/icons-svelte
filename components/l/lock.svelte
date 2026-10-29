<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhq0_w-kq.css';
import '../../css/j/j95qubcnh.css';
import '../../css/x/xpavwbcrh.css';
import '../../css/v/vu9ry25jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhq0_w-kq wm-a"/><path class="j95qubcnh wm-k"/><path class="wm-k xpavwbcrh"/><path class="vu9ry25jl wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:lock" {...props}></Icon>
