<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bd6ig9a2x.css';
import '../../css/b/b-n-y5s-l.css';
import '../../css/d/d5fvesbdz.css';
import '../../css/k/kbu36ebbb.css';
import '../../css/h/h2qxo6bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bd6ig9a2x"/><path class="b-n-y5s-l"/><path class="d5fvesbdz"/><path class="kbu36ebbb"/><path class="h2qxo6bes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:basketball-bold" {...props}></Icon>
