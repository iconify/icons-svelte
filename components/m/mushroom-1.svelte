<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb4uxyb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="zb4uxyb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:mushroom-1" {...props}></Icon>
