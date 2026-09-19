<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/r/r-qclcbiq.css';
import '../../css/d/d1igh63-p.css';
import '../../css/k/kxc2n7muj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="r-qclcbiq"/><path clip-rule="evenodd" class="d1igh63-p"/><path class="kxc2n7muj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:open-door" {...props}></Icon>
