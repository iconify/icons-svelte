<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcssgdcnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dcssgdcnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-lock-solid" {...props}></Icon>
