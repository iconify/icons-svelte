<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsjrd1_7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsjrd1_7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-dots-2-filled" {...props}></Icon>
