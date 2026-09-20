<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oasgoj2dk.css';
import '../../css/u/uf9v5dfhb.css';
import '../../css/o/o1vr-2ost.css';
import '../../css/x/x3ibz2bfz.css';
import '../../css/x/xojntycxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="oasgoj2dk"/><ellipse class="uf9v5dfhb"/><path class="o1vr-2ost"/><ellipse class="x3ibz2bfz"/><path class="xojntycxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:myspace-circle" {...props}></Icon>
