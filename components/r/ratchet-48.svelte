<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp-qlgb3c.css';
import '../../css/u/uw0hg1f1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kp-qlgb3c"/><path class="uw0hg1f1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ratchet-48" {...props}></Icon>
