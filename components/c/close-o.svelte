<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebldvkbho.css';
import '../../css/o/ok5a-4evb.css';
import '../../css/s/skzxnomci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ebldvkbho"/><path class="ok5a-4evb"/><path class="skzxnomci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:close-o" {...props}></Icon>
