<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd9hhcbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd9hhcbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cart-x" {...props}></Icon>
