<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxm40qhvn.css';
import '../../css/a/alf2ikb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="lxm40qhvn"/><path clip-rule="evenodd" class="alf2ikb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:download-circle-1" {...props}></Icon>
