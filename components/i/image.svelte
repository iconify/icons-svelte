<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/szl-vpbku.css';
import '../../css/n/n1-nh8qnp.css';
import '../../css/g/g6flz5byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="szl-vpbku"/><path class="n1-nh8qnp"/><path class="g6flz5byn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:image" {...props}></Icon>
