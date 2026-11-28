<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs0n83b1m.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qyvn42bbq.css';
import '../../css/t/t8x-nbhsm.css';
import '../../css/c/cxy8b7bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs0n83b1m secondary"/><g class="dt0cm9dhy primary"><path class="qyvn42bbq"/><path class="t8x-nbhsm"/><path class="cxy8b7bmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:diamond-alert-duo" {...props}></Icon>
