<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpx05ibmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpx05ibmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:puzzle" {...props}></Icon>
