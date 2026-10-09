<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpx9c7b2s.css';
import '../../css/t/txjejvbqg.css';
import '../../css/b/bl7dph6nh.css';
import '../../css/e/evm-be1zu.css';
import '../../css/n/njoh_kbze.css';
import '../../css/m/mbh0wwbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rpx9c7b2s"/><path class="txjejvbqg"/><path class="bl7dph6nh"/><path class="evm-be1zu"/><path class="njoh_kbze"/><path class="mbh0wwbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-wind-20" {...props}></Icon>
