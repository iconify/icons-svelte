<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngz2hwbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngz2hwbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-reply-fill" {...props}></Icon>
