<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frgdqtr2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="frgdqtr2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-square-reply-filled" {...props}></Icon>
