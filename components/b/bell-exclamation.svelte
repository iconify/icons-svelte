<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzfljrblz.css';
import '../../css/s/saso1vbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xzfljrblz"/><path class="saso1vbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:bell-exclamation" {...props}></Icon>
