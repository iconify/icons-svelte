<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebldvkbho.css';
import '../../css/r/r6mnptbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ebldvkbho"/><path class="r6mnptbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:clock" {...props}></Icon>
