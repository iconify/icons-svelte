<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhqruzgqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lhqruzgqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:camera-video-remix" {...props}></Icon>
