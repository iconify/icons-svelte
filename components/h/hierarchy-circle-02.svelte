<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gglsf5jgx.css';
import '../../css/k/kxe36xeye.css';
import '../../css/k/kc3talsdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gglsf5jgx"/><path class="kxe36xeye"/><path class="kc3talsdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hierarchy-circle-02" {...props}></Icon>
