<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsc84ccge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsc84ccge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-t-square" {...props}></Icon>
