<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8f08ivcr.css';
import '../../css/u/ufzvs3byi.css';
import '../../css/d/d27j7obsk.css';
import '../../css/g/gxxzd4_qb.css';
import '../../css/d/d_u133t5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h8f08ivcr"/><path class="ufzvs3byi"/><path class="d27j7obsk"/><path class="gxxzd4_qb"/><path class="d_u133t5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-check-48-bold" {...props}></Icon>
