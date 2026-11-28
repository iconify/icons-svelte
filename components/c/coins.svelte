<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a7mgnpb7z.css';
import '../../css/n/nk3w2sk1d.css';
import '../../css/g/g8hv7acos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a7mgnpb7z"/><path class="nk3w2sk1d"/><path class="g8hv7acos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:coins" {...props}></Icon>
