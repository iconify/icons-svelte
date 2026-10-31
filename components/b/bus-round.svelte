<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuo_0fbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuo_0fbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bus-round" {...props}></Icon>
