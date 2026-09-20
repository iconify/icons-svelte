<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk5yjk1vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zk5yjk1vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:gift-solid" {...props}></Icon>
