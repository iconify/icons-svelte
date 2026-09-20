<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f2gl3acpc.css';
import '../../css/x/xc0yxgbay.css';
import '../../css/u/udt3hqb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f2gl3acpc"/><path clip-rule="evenodd" class="xc0yxgbay"/><path class="udt3hqb4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:plug" {...props}></Icon>
