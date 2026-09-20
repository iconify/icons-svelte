<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y4rb44b0t.css';
import '../../css/i/i5w7s1btf.css';
import '../../css/w/wl2no6bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="y4rb44b0t"/><path class="i5w7s1btf"/><path class="wl2no6bnr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:password3" {...props}></Icon>
