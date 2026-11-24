<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo1c8-b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo1c8-b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-filled" {...props}></Icon>
