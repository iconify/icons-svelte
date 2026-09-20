<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmaeb6bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xmaeb6bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-medium-1" {...props}></Icon>
