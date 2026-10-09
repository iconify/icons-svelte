<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4lrodbjn.css';
import '../../css/y/ykzqhcc_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l4lrodbjn"/><path class="ykzqhcc_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:podium-48" {...props}></Icon>
