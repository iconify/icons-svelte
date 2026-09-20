<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqax-6b-d.css';
import '../../css/f/fic52hb-m.css';
import '../../css/m/mtx6jf4xy.css';
import '../../css/o/o8x1rfpnw.css';
import '../../css/k/k0b12kb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="fic52hb-m"/><path class="mtx6jf4xy"/><path class="o8x1rfpnw"/><path class="k0b12kb_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:dna" {...props}></Icon>
