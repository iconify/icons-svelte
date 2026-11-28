<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tawo86brd.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lb5tddpfm.css';
import '../../css/f/f_1d46bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tawo86brd"/><g class="dt0cm9dhy primary"><path class="lb5tddpfm"/><path class="f_1d46bly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-left-dash-duo" {...props}></Icon>
