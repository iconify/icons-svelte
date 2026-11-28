<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh83pkqjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh83pkqjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ceiling-lamp-check" {...props}></Icon>
