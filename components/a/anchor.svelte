<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pt93twbsc.css';
import '../../css/w/wv5f_1brg.css';
import '../../css/d/dsp6khz0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pt93twbsc"/><circle class="wv5f_1brg"/><path class="dsp6khz0q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:anchor" {...props}></Icon>
