<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8f_aibnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8f_aibnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-question-mark-filled" {...props}></Icon>
