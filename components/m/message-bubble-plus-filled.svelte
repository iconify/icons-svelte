<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lslr_dbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lslr_dbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-plus-filled" {...props}></Icon>
