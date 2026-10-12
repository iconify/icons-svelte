<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzpmmxj6m.css';
import '../../css/e/ez71_mloi.css';
import '../../css/h/hc5gysb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jzpmmxj6m"/><path class="ez71_mloi"/><path class="hc5gysb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cnc-machine-48-bold" {...props}></Icon>
