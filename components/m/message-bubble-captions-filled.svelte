<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5-xnrwut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5-xnrwut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-captions-filled" {...props}></Icon>
