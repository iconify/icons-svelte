<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnuq4e15h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnuq4e15h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-exclamation-filled" {...props}></Icon>
