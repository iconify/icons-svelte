<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlsrljbwz.css';
import '../../css/v/veuurfbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rlsrljbwz"/><path class="veuurfbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:compliance-48" {...props}></Icon>
