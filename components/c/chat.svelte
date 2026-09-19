<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypnl_3blq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ypnl_3blq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:chat" {...props}></Icon>
