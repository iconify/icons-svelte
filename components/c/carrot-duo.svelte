<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj3ugqhvs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/ett11-bch.css';
import '../../css/w/ws2q1my1b.css';
import '../../css/h/hjp5ozb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sj3ugqhvs"/><g class="dt0cm9dhy primary"><path class="ett11-bch"/><path class="ws2q1my1b"/><path class="hjp5ozb1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:carrot-duo" {...props}></Icon>
