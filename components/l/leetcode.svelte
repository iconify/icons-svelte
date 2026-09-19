<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkm7mbckp.css';
import '../../css/s/s4uphz44s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkm7mbckp"/><path class="s4uphz44s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:leetcode" {...props}></Icon>
