<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eirgzobiv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mie31z6an.css';
import '../../css/v/vw09pmb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eirgzobiv secondary"/><g class="dt0cm9dhy primary"><path class="mie31z6an"/><path class="vw09pmb1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-right-square-duo" {...props}></Icon>
