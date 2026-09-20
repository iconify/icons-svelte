<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb2a1qwds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zb2a1qwds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:plane" {...props}></Icon>
