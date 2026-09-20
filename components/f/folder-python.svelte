<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phu1k1bve.css';
import '../../css/i/irkldebla.css';
import '../../css/l/lbwm2mbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="phu1k1bve"/><path class="irkldebla"/><path class="lbwm2mbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-python" {...props}></Icon>
