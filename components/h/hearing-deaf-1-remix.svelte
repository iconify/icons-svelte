<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uixa-ip4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uixa-ip4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hearing-deaf-1-remix" {...props}></Icon>
