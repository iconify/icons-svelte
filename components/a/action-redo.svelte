<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkz65tbzv.css';
import '../../css/b/bm74p9apf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gkz65tbzv"/><path class="bm74p9apf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:action-redo" {...props}></Icon>
