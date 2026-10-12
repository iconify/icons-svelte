<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_hx_ibsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_hx_ibsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:arrow-big-down-dash-filled" {...props}></Icon>
