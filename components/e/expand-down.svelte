<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/l/l2h99cbcg.css';
import '../../css/x/xmie1ejsr.css';
import '../../css/k/k-k8-gbsm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGynakgbDH"><g class="ufeehvblu"><path class="l2h99cbcg"/><path class="xmie1ejsr"/><path class="k-k8-gbsm"/></g></mask></defs><path mask="url(#SVGynakgbDH)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:expand-down" {...props}></Icon>
