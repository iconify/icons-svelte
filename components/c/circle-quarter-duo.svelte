<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzie_n95r.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/h/hw30gi65f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzie_n95r secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="hw30gi65f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-quarter-duo" {...props}></Icon>
