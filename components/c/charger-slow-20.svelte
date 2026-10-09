<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6njav50m.css';
import '../../css/o/oljydkxyh.css';
import '../../css/x/xoyjgxgiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p6njav50m"/><path class="oljydkxyh"/><path class="xoyjgxgiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-slow-20" {...props}></Icon>
