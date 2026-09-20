<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhsg9bc_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhsg9bc_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:analytics" {...props}></Icon>
