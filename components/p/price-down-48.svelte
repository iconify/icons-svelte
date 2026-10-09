<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1ftczb6h.css';
import '../../css/d/dlrxuzy1s.css';
import '../../css/k/kyrmlcowv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g1ftczb6h"/><path class="dlrxuzy1s"/><path class="kyrmlcowv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:price-down-48" {...props}></Icon>
