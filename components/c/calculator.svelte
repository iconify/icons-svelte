<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeo51ebfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yeo51ebfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calculator" {...props}></Icon>
