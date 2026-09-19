<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm8vpmbuj.css';
import '../../css/y/y0l3i_qwp.css';
import '../../css/m/mxgov2bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bm8vpmbuj"/><path class="y0l3i_qwp"/><circle class="mxgov2bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:cable-release" {...props}></Icon>
