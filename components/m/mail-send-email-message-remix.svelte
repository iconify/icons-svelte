<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmu1be8bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hmu1be8bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-send-email-message-remix" {...props}></Icon>
