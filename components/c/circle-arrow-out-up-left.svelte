<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy5fo_y_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy5fo_y_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:circle-arrow-out-up-left" {...props}></Icon>
