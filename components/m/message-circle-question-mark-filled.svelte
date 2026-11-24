<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8t8hmbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l8t8hmbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-question-mark-filled" {...props}></Icon>
