<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxo33drqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sxo33drqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:family-restroom-symbol" {...props}></Icon>
