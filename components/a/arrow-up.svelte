<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/v0g_z_j1d.css';
import '../../css/y/yynt2ibtm.css';
import '../../css/b/bhrwz6oki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="v0g_z_j1d"/><path class="yynt2ibtm"/><path class="bhrwz6oki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:arrow-up" {...props}></Icon>
