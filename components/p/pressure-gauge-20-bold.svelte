<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7slukbjf.css';
import '../../css/h/hyz9tubor.css';
import '../../css/y/yu8ceqbjs.css';
import '../../css/q/q425r9b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u7slukbjf"/><path class="hyz9tubor"/><path class="yu8ceqbjs"/><path class="q425r9b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pressure-gauge-20-bold" {...props}></Icon>
