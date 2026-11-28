<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eirgzobiv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mie31z6an.css';
import '../../css/l/lsums62it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eirgzobiv secondary"/><g class="dt0cm9dhy primary"><path class="mie31z6an"/><path class="lsums62it"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:close-square-duo" {...props}></Icon>
