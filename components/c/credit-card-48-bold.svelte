<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6xr_117y.css';
import '../../css/e/ej4s9gber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p6xr_117y"/><path class="ej4s9gber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:credit-card-48-bold" {...props}></Icon>
