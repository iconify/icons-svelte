<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chy3nfbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="chy3nfbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:downright" {...props}></Icon>
