<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh95nccwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh95nccwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-turn-right-down-expressive" {...props}></Icon>
