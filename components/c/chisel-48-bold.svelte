<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wveopm0na.css';
import '../../css/o/o0pzhhiin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wveopm0na"/><path class="o0pzhhiin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chisel-48-bold" {...props}></Icon>
