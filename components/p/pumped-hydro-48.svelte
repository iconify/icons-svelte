<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0377flqh.css';
import '../../css/m/mc3iqybwb.css';
import '../../css/z/zxfgagwie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a0377flqh"/><path class="mc3iqybwb"/><path class="zxfgagwie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pumped-hydro-48" {...props}></Icon>
