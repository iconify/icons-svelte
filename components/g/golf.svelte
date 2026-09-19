<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_6u2mhvb.css';
import '../../css/q/qm-3n6bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_6u2mhvb"/><path class="qm-3n6bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:golf" {...props}></Icon>
