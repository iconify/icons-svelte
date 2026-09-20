<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/ngnrt3bip.css';
import '../../css/i/im44ngbpl.css';
import '../../css/q/qb_upbbvc.css';
import '../../css/j/jxl67pbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ngnrt3bip"/><path class="im44ngbpl"/><path class="qb_upbbvc"/><circle class="jxl67pbry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:refresh-ccw-dot" {...props}></Icon>
