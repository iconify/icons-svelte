<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/io2mm3b4i.css';
import '../../css/d/dfep9nb_v.css';
import '../../css/u/ug1uowu6z.css';
import '../../css/h/hbb908j_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="io2mm3b4i"/><path class="dfep9nb_v"/><path class="ug1uowu6z"/><path class="hbb908j_v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bill-bold-duotone" {...props}></Icon>
