<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmzmn_bsa.css';
import '../../css/t/tf5y_6b6k.css';
import '../../css/k/k6e-3tb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hmzmn_bsa"/><path class="tf5y_6b6k"/><path class="k6e-3tb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pickup-truck-48-bold" {...props}></Icon>
