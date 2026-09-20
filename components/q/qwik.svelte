<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8aw24b0h.css';
import '../../css/t/tnv3g-b3r.css';
import '../../css/c/cduhi3biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r8aw24b0h"/><path class="tnv3g-b3r"/><path class="cduhi3biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qwik" {...props}></Icon>
