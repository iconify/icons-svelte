<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/irq2_dbnj.css';
import '../../css/r/reibu1jor.css';
import '../../css/p/ps1k-2b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="irq2_dbnj"/><path clip-rule="evenodd" class="reibu1jor"/><path class="ps1k-2b5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dhis2-logo-outline" {...props}></Icon>
