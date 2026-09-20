<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnwm40bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qnwm40bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:download-tray-remix" {...props}></Icon>
