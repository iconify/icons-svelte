<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_y8nv_ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_y8nv_ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bookmark-edit-line" {...props}></Icon>
