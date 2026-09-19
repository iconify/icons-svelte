<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quy6tdbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quy6tdbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:coupon" {...props}></Icon>
