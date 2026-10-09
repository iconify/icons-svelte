<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7vk3y3bo.css';
import '../../css/r/rpx2p260d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t7vk3y3bo"/><path class="rpx2p260d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:burger-48-bold" {...props}></Icon>
