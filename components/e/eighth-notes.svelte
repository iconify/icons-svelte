<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh1ch4dcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zh1ch4dcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eighth-notes" {...props}></Icon>
