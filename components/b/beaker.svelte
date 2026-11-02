<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/c/cc0mz8ytr.css';
import '../../css/l/lf60ieb-k.css';
import '../../css/e/emi3zzq4a.css';
import '../../css/o/ogmki_bjr.css';
import '../../css/x/xv_z_ubpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="cc0mz8ytr"/><path class="lf60ieb-k"/><path class="emi3zzq4a"/><path class="ogmki_bjr"/><path class="xv_z_ubpb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:beaker" {...props}></Icon>
