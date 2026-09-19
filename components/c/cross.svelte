<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh4t1tb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh4t1tb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:cross" {...props}></Icon>
