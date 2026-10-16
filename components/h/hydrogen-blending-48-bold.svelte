<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1u8_-b9b.css';
import '../../css/a/a_6bvzblh.css';
import '../../css/d/d32_g_rfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v1u8_-b9b"/><path class="a_6bvzblh"/><path class="d32_g_rfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-blending-48-bold" {...props}></Icon>
