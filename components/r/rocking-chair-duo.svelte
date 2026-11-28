<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mxiihibxh.css';
import '../../css/u/u5egpobzl.css';
import '../../css/w/wmsjuibuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mxiihibxh"/><path class="u5egpobzl"/><path class="wmsjuibuj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:rocking-chair-duo" {...props}></Icon>
