<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebldvkbho.css';
import '../../css/y/y5vv9ubra.css';
import '../../css/b/b922yzmjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ebldvkbho"/><path class="y5vv9ubra"/><path class="b922yzmjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:arrow-right" {...props}></Icon>
