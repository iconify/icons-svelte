<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvxm07bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mvxm07bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-multiple-window-solid" {...props}></Icon>
