<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v84_akkuy.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uijgoup2v.css';
import '../../css/i/i1u2bqb_t.css';
import '../../css/r/rqwm_hbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary v84_akkuy"/><g class="dt0cm9dhy primary"><path class="uijgoup2v"/><path class="i1u2bqb_t"/><path class="rqwm_hbww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flip-horizontal-duo" {...props}></Icon>
