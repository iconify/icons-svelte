<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n0i-vgb_k.css';
import '../../css/f/fjho7nbhe.css';
import '../../css/p/pdujj3blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n0i-vgb_k"/><path class="fjho7nbhe"/><path class="pdujj3blx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cleaning-sign" {...props}></Icon>
