<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhkcfg0wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhkcfg0wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:coins-plus" {...props}></Icon>
