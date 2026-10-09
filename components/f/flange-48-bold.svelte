<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_6rndbde.css';
import '../../css/t/ti_1d3blo.css';
import '../../css/k/kew39h_ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e_6rndbde"/><path class="ti_1d3blo"/><path class="kew39h_ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flange-48-bold" {...props}></Icon>
