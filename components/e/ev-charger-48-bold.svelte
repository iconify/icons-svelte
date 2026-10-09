<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rin2rdbyp.css';
import '../../css/y/yoo-x4z3f.css';
import '../../css/d/d27j7obsk.css';
import '../../css/q/qb_7iivgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rin2rdbyp"/><path class="yoo-x4z3f"/><path class="d27j7obsk"/><path class="qb_7iivgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-48-bold" {...props}></Icon>
