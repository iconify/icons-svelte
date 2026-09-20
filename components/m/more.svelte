<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qcx76zaxv.css';
import '../../css/p/peiq2hfxm.css';
import '../../css/b/bgy1389lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="qcx76zaxv"/><circle class="peiq2hfxm"/><circle class="bgy1389lr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:more" {...props}></Icon>
