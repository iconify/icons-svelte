<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz_kbtsof.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wbizk1a7x.css';
import '../../css/i/ip79ax0mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz_kbtsof secondary"/><g class="dt0cm9dhy primary"><path class="wbizk1a7x"/><path class="ip79ax0mg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:garage-open-duo" {...props}></Icon>
