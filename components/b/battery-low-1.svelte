<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd-q_lbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zd-q_lbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-low-1" {...props}></Icon>
