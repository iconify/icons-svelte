<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx66pva8x.css';
import '../../css/l/l67st8b5a.css';
import '../../css/s/s_a69j5sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx66pva8x wm-k"/><path class="l67st8b5a wm-a"/><path class="s_a69j5sy wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:image" {...props}></Icon>
