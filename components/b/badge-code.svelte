<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l4--ovbba.css';
import '../../css/q/qbdsnuxpd.css';
import '../../css/n/n5_uowbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l4--ovbba"/><path class="qbdsnuxpd"/><path class="n5_uowbnw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-code" {...props}></Icon>
