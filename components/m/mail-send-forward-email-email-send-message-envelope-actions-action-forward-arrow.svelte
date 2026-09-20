<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtzh11bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rtzh11bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mail-send-forward-email-email-send-message-envelope-actions-action-forward-arrow" {...props}></Icon>
