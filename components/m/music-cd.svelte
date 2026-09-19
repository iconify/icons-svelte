<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/b/b08in11er.css';
import '../../css/z/zq9ep78uu.css';
import '../../css/i/im0mfzb0p.css';
import '../../css/j/jgfok7b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="b08in11er"/><path class="zq9ep78uu"/><path class="im0mfzb0p"/><path class="jgfok7b9j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:music-cd" {...props}></Icon>
