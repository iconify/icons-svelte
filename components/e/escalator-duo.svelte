<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhxiasruy.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h0nez9b5x.css';
import '../../css/k/k4tei8bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhxiasruy secondary"/><g class="dt0cm9dhy primary"><path class="h0nez9b5x"/><path class="k4tei8bid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:escalator-duo" {...props}></Icon>
