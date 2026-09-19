<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kesxv2ddf.css';
import '../../css/c/c5tjsfbln.css';
import '../../css/s/s2vaych-g.css';
import '../../css/q/qlg8_6z_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="kesxv2ddf"/><path clip-rule="evenodd" class="c5tjsfbln"/><path class="s2vaych-g"/><path clip-rule="evenodd" class="qlg8_6z_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:hourglass" {...props}></Icon>
