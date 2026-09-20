<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3t15vy2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="l3t15vy2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-play" {...props}></Icon>
