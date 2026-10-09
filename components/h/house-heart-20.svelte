<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpx9c7b2s.css';
import '../../css/d/dw6_5lnpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rpx9c7b2s"/><path class="dw6_5lnpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-heart-20" {...props}></Icon>
