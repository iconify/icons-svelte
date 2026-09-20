<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd_r1krus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wd_r1krus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flash-3" {...props}></Icon>
