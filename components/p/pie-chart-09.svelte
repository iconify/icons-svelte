<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr2y-vbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr2y-vbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pie-chart-09" {...props}></Icon>
