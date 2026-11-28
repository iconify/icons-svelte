<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psxbs1bui.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l4--ovbba.css';
import '../../css/b/bcjkb_2eo.css';
import '../../css/q/qbyro8bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psxbs1bui secondary"/><g class="dt0cm9dhy primary"><path class="l4--ovbba"/><path class="bcjkb_2eo"/><path class="qbyro8bns"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-dollar-duo" {...props}></Icon>
