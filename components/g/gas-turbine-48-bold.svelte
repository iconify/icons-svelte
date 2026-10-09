<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubh0c368i.css';
import '../../css/b/b1075nben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ubh0c368i"/><path class="b1075nben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-turbine-48-bold" {...props}></Icon>
