<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5ezajb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m5ezajb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:chat-bubble-oval-smiley-1-solid" {...props}></Icon>
