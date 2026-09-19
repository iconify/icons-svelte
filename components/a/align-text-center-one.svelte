<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/c/cahgxccet.css';
import '../../css/i/iu_7h2b0u.css';
import '../../css/j/jtgskbcrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="cahgxccet"/><path class="iu_7h2b0u"/><path class="jtgskbcrm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:align-text-center-one" {...props}></Icon>
