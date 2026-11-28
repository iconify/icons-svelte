<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wttwc7bye.css';
import '../../css/p/pgt6w1b0j.css';
import '../../css/q/qtmyn7x6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wttwc7bye"/><path class="pgt6w1b0j"/><path class="qtmyn7x6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:metronome" {...props}></Icon>
