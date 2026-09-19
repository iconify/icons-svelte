<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc0cjx2pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wc0cjx2pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:finished" {...props}></Icon>
