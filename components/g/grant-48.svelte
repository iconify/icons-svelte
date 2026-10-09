<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpeu_j1mo.css';
import '../../css/l/lyr6s0wuk.css';
import '../../css/b/by6gobvlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tpeu_j1mo"/><path class="lyr6s0wuk"/><path class="by6gobvlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grant-48" {...props}></Icon>
