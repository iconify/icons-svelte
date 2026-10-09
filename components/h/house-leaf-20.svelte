<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpx9c7b2s.css';
import '../../css/a/a_0kltb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rpx9c7b2s"/><path class="a_0kltb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-leaf-20" {...props}></Icon>
