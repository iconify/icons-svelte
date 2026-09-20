<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg8yd53zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg8yd53zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dingding-fill" {...props}></Icon>
