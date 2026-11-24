<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4iz6j5pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j4iz6j5pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-heart-filled" {...props}></Icon>
