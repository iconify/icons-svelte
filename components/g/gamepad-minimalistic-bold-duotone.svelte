<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c3ujshblw.css';
import '../../css/n/ndsw3g6vj.css';
import '../../css/n/nlp0xzmnw.css';
import '../../css/g/g-iv8b6la.css';
import '../../css/b/b2ecdbcpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c3ujshblw"/><path class="ndsw3g6vj"/><path class="nlp0xzmnw"/><path class="g-iv8b6la"/><path class="b2ecdbcpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gamepad-minimalistic-bold-duotone" {...props}></Icon>
