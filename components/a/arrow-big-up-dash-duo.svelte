<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dov2pdbuq.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h_2abro7x.css';
import '../../css/n/nv6nssw1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dov2pdbuq secondary"/><g class="dt0cm9dhy primary"><path class="h_2abro7x"/><path class="nv6nssw1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-up-dash-duo" {...props}></Icon>
