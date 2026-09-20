<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en_uyyw_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en_uyyw_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mailbox-up-outline" {...props}></Icon>
