<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec_lwoagr.css';
import '../../css/f/flbf2qb7n.css';
import '../../css/t/t7622gbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ec_lwoagr"/><path class="flbf2qb7n"/><path class="t7622gbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:motion-sensor-48-bold" {...props}></Icon>
