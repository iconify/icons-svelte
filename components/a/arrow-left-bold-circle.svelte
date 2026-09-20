<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_cor3_8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_cor3_8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-left-bold-circle" {...props}></Icon>
