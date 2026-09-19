<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6g3u8wjy.css';
import '../../css/u/ughd8vbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c6g3u8wjy"/><path class="ughd8vbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ice-cream" {...props}></Icon>
