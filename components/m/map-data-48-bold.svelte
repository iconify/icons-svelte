<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9jxscckh.css';
import '../../css/h/hwk25ejtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r9jxscckh"/><path class="hwk25ejtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-data-48-bold" {...props}></Icon>
