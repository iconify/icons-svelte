<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc8rsybkr.css';
import '../../css/m/mabcrgb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lc8rsybkr"/><path class="mabcrgb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-dropup" {...props}></Icon>
