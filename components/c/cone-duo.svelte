<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpi92pwpd.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/u5mnzf2gv.css';
import '../../css/s/sgqd9obdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary vpi92pwpd"/><g class="dt0cm9dhy primary"><path class="u5mnzf2gv"/><path class="sgqd9obdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cone-duo" {...props}></Icon>
