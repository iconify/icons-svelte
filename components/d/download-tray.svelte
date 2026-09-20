<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1f2vmboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r1f2vmboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:download-tray" {...props}></Icon>
