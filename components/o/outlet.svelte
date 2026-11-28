<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/k/kvjb9cclc.css';
import '../../css/g/gd2be0boy.css';
import '../../css/u/uh9juqbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ud95brdct"/><path class="kvjb9cclc"/><path class="gd2be0boy"/><path class="uh9juqbza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:outlet" {...props}></Icon>
