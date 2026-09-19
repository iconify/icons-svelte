<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yinali4xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yinali4xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:play-forwards" {...props}></Icon>
