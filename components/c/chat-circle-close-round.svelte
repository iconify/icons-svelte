<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcw00slrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcw00slrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-close-round" {...props}></Icon>
