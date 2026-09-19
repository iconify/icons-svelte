<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0xzvjsfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m0xzvjsfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circledownload" {...props}></Icon>
