<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpel3hezc.css';
import '../../css/b/b5o99dp3a.css';
import '../../css/g/g0_zv0bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tpel3hezc"/><path class="b5o99dp3a"/><path class="g0_zv0bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-histogram-48-bold" {...props}></Icon>
