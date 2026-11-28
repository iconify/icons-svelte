<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inwtukrhj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i5f0lcbnp.css';
import '../../css/p/pt9ctxglj.css';
import '../../css/r/r4bva5bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inwtukrhj secondary"/><g class="dt0cm9dhy primary"><path class="i5f0lcbnp"/><path class="pt9ctxglj"/><path class="r4bva5bde"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ice-cream-cone-duo" {...props}></Icon>
