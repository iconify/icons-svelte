<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp0y3rb0u.css';
import '../../css/z/zxw2msv7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jp0y3rb0u"/><path class="zxw2msv7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-bookmark-1" {...props}></Icon>
