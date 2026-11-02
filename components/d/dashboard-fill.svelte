<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt7hbcc_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt7hbcc_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dashboard-fill" {...props}></Icon>
