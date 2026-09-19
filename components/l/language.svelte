<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue7-78_gf.css';
import '../../css/h/hndxaub8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ue7-78_gf"/><path class="hndxaub8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:language" {...props}></Icon>
