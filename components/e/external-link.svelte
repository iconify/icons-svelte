<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1f7-bc3e.css';
import '../../css/q/qf2khhs5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="e1f7-bc3e"/><path class="qf2khhs5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:external-link" {...props}></Icon>
