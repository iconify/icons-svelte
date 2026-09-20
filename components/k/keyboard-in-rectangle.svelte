<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxmdoachy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xxmdoachy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:keyboard-in-rectangle" {...props}></Icon>
