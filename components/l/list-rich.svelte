<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy2-xpbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yy2-xpbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:list-rich" {...props}></Icon>
