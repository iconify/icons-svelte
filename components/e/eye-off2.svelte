<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r8zd38n0h.css';
import '../../css/g/gl1daib4n.css';
import '../../css/z/zw1qlkb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r8zd38n0h"/><path class="gl1daib4n"/><path class="zw1qlkb7m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:eye-off2" {...props}></Icon>
