<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu5u_dbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu5u_dbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-chart-2-line" {...props}></Icon>
