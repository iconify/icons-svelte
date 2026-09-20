<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me1w258bl.css';
import '../../css/e/e0ia1ccfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="me1w258bl"/><path class="e0ia1ccfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flint" {...props}></Icon>
