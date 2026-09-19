<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-kgrhb0e.css';
import '../../css/c/clr-_gv_i.css';
import '../../css/p/ptl4ptbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n-kgrhb0e"/><path class="clr-_gv_i"/><path class="ptl4ptbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bug-outline" {...props}></Icon>
