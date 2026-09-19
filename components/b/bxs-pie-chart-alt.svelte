<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skm4p0brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skm4p0brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-pie-chart-alt" {...props}></Icon>
