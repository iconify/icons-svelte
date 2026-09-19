<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx2bwzbqr.css';
import '../../css/c/c3o_ezbrt.css';
import '../../css/h/h70urzc4n.css';
import '../../css/l/lk8u_z3zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qx2bwzbqr"/><path class="c3o_ezbrt"/><path class="h70urzc4n"/><path class="lk8u_z3zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:faq" {...props}></Icon>
