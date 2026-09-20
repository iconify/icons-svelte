<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lm9jkgbkg.css';
import '../../css/s/s7ud3zb9r.css';
import '../../css/r/rlomcqbno.css';
import '../../css/p/pclxeftyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lm9jkgbkg"/><path class="s7ud3zb9r"/><path clip-rule="evenodd" class="rlomcqbno"/><path class="pclxeftyv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lamp-duotone" {...props}></Icon>
