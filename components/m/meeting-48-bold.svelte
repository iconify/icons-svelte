<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5ciubb6p.css';
import '../../css/i/iowuvxnvk.css';
import '../../css/r/rw-4knbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e5ciubb6p"/><path class="iowuvxnvk"/><path class="rw-4knbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:meeting-48-bold" {...props}></Icon>
