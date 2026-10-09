<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghgrl9bnl.css';
import '../../css/q/qcs6rdphe.css';
import '../../css/x/xpp-7oufq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ghgrl9bnl"/><path class="qcs6rdphe"/><path class="xpp-7oufq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offshore-platform-48-bold" {...props}></Icon>
