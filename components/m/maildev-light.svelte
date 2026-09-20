<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_ogl0bpc.css';
import '../../css/m/mtxmfcb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_ogl0bpc"/><path class="mtxmfcb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maildev-light" {...props}></Icon>
