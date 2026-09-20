<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3bqa_bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b3bqa_bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-send-email-message-solid" {...props}></Icon>
