<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-l1pd0_w.css';
import '../../css/a/aghnw_bgv.css';
import '../../css/l/l_1yt4cmi.css';
import '../../css/m/mg82_uzpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h-l1pd0_w"><path clip-rule="evenodd" class="aghnw_bgv"/><path class="l_1yt4cmi"/><path clip-rule="evenodd" class="mg82_uzpj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:flask-solid" {...props}></Icon>
