<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r9g1uycax.css';
import '../../css/m/mie1t6b-r.css';
import '../../css/k/kqrp2fbsl.css';
import '../../css/j/j0jzcbbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r9g1uycax"/><path clip-rule="evenodd" class="mie1t6b-r"/><path class="kqrp2fbsl"/><path class="j0jzcbbwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:eyeglasses-24px" {...props}></Icon>
