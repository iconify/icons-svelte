<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8ffwrbpp.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vwqu088iv.css';
import '../../css/i/ige5ecbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8ffwrbpp secondary"/><g class="dt0cm9dhy primary"><path class="vwqu088iv"/><path class="ige5ecbiu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cylinder-duo" {...props}></Icon>
