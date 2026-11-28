<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psxbs1bui.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l4--ovbba.css';
import '../../css/q/qezbnzq0b.css';
import '../../css/s/sez1bjdtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psxbs1bui secondary"/><g class="dt0cm9dhy primary"><path class="l4--ovbba"/><path class="qezbnzq0b"/><path class="sez1bjdtf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-alert-duo" {...props}></Icon>
