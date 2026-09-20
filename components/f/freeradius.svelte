<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9jd4lb3h.css';
import '../../css/q/qx2necw3z.css';
import '../../css/f/fifs5bbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f9jd4lb3h"/><circle class="qx2necw3z"/><path class="fifs5bbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freeradius" {...props}></Icon>
