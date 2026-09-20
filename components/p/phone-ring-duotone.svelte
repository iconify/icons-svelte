<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mzq9_bcst.css';
import '../../css/g/g93bdwbpy.css';
import '../../css/j/jfquk0ace.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mzq9_bcst"/><path class="g93bdwbpy"/><path clip-rule="evenodd" class="jfquk0ace"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone-ring-duotone" {...props}></Icon>
