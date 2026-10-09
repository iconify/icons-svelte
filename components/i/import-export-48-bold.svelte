<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ampl8-clf.css';
import '../../css/d/d81cmo-oy.css';
import '../../css/i/ijl0gbtvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ampl8-clf"/><path class="d81cmo-oy"/><path class="ijl0gbtvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:import-export-48-bold" {...props}></Icon>
