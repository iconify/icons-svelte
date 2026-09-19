<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e7s3h_45j.css';
import '../../css/x/x_v6dlman.css';
import '../../css/m/mg1b38bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e7s3h_45j"/><path class="x_v6dlman"/><path class="mg1b38bzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:angry-bird" {...props}></Icon>
