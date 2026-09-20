<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz1o6hb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wz1o6hb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:navigation-arrow-off" {...props}></Icon>
