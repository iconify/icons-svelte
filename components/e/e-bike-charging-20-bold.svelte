<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koyov2bfs.css';
import '../../css/a/aez0dwbdt.css';
import '../../css/k/keapg2bjm.css';
import '../../css/b/b9s0npblv.css';
import '../../css/u/uin4slb1r.css';
import '../../css/y/yyg0fywys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="koyov2bfs"/><path class="aez0dwbdt"/><path class="keapg2bjm"/><path class="b9s0npblv"/><path class="uin4slb1r"/><path class="yyg0fywys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:e-bike-charging-20-bold" {...props}></Icon>
