<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_1d6ub_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_1d6ub_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flash-auto" {...props}></Icon>
