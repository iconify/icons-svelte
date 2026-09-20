<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf578kboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf578kboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:expand-vertical" {...props}></Icon>
