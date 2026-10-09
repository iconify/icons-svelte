<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu7_ubb2h.css';
import '../../css/g/g11ocj1zr.css';
import '../../css/x/xf66x87di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gu7_ubb2h"/><path class="g11ocj1zr"/><path class="xf66x87di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:archive-48" {...props}></Icon>
