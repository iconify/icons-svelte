<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0rtidb-e.css';
import '../../css/f/fh1vxnxeg.css';
import '../../css/s/s1s0bim7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a z0rtidb-e"/><path class="fh1vxnxeg wm-k"/><path class="s1s0bim7b wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:cursor" {...props}></Icon>
