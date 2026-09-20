<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jknbwyp-h.css';
import '../../css/l/lzloo5hnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jknbwyp-h"/><path class="lzloo5hnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:location-line" {...props}></Icon>
