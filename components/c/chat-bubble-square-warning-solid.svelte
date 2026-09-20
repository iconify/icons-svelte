<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzdp6tnri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vzdp6tnri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:chat-bubble-square-warning-solid" {...props}></Icon>
