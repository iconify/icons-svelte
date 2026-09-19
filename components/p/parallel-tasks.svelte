<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhqdfsbas.css';
import '../../css/l/l8vyo8zlh.css';
import '../../css/e/e_kkwobnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fhqdfsbas"/><path class="l8vyo8zlh"/><path class="e_kkwobnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:parallel-tasks" {...props}></Icon>
