<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/o/o8x38jbfa.css';
import '../../css/s/sce5bfb4n.css';
import '../../css/c/czqpd_v7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="o8x38jbfa"/><circle class="sce5bfb4n"/><path class="czqpd_v7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:people-bottom-card" {...props}></Icon>
