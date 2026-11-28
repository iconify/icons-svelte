<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m0g21rfgt.css';
import '../../css/l/lbmbikban.css';
import '../../css/f/fwvwu22pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m0g21rfgt"/><path class="lbmbikban"/><path class="fwvwu22pc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-from-line-duo" {...props}></Icon>
