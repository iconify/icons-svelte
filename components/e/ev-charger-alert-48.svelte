<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_60udxbz.css';
import '../../css/d/dpwi3bccu.css';
import '../../css/p/p7kyn66pi.css';
import '../../css/i/ib8r12brx.css';
import '../../css/b/bxzxb8v8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k_60udxbz"/><path class="dpwi3bccu"/><path class="p7kyn66pi"/><path class="ib8r12brx"/><path class="bxzxb8v8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-alert-48" {...props}></Icon>
