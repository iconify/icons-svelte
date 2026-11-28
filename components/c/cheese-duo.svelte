<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2d3of8ot.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nl_qurb3s.css';
import '../../css/k/kf2fi9bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2d3of8ot secondary"/><g class="dt0cm9dhy primary"><path class="nl_qurb3s"/><path class="kf2fi9bdy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cheese-duo" {...props}></Icon>
