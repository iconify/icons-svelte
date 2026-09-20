<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buo6a4byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="buo6a4byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:inbox-tray-1-remix" {...props}></Icon>
