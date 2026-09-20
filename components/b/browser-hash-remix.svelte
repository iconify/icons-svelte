<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyzc6vlcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nyzc6vlcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-hash-remix" {...props}></Icon>
