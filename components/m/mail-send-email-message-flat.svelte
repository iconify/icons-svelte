<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd6hm15ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cd6hm15ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:mail-send-email-message-flat" {...props}></Icon>
