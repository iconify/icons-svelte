<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2mzgicbz.css';
import '../../css/h/h48rmab4l.css';
import '../../css/t/t1hj47b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b2mzgicbz"/><path class="h48rmab4l"/><path class="t1hj47b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockflare-light" {...props}></Icon>
