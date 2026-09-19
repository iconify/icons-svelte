<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/m/ma5ivp-0g.css';
import '../../css/m/mp5ioowxd.css';
import '../../css/f/fzg-l0b9g.css';
import '../../css/v/vy9t1lb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="ma5ivp-0g"/><path class="mp5ioowxd"/><path class="fzg-l0b9g"/><path class="vy9t1lb6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:devices" {...props}></Icon>
