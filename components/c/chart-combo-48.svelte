<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyyebzbnj.css';
import '../../css/w/wz2svgbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tyyebzbnj"/><path class="wz2svgbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-combo-48" {...props}></Icon>
