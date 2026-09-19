<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2108y1ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":642,"height":717};
const content = `<path class="p2108y1ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:flag" {...props}></Icon>
