<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/ve1i9wjpw.css';
import '../../css/u/uxz72gbpi.css';
import '../../css/f/fvhf7ybpe.css';
import '../../css/t/t7ag5wbbh.css';
import '../../css/o/oercy74sh.css';
import '../../css/l/lh6igabhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ve1i9wjpw"/><path class="uxz72gbpi"/><path class="fvhf7ybpe"/><path class="t7ag5wbbh"/><path class="oercy74sh"/><path class="lh6igabhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pig" {...props}></Icon>
