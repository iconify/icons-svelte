<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlst_c_vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlst_c_vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-line" {...props}></Icon>
