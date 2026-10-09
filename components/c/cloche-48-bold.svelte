<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub-di_unr.css';
import '../../css/d/dx_dw6rtl.css';
import '../../css/g/g-5s0nbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ub-di_unr"/><path class="dx_dw6rtl"/><path class="g-5s0nbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloche-48-bold" {...props}></Icon>
