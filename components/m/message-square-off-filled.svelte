<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7ukzsz6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7ukzsz6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-square-off-filled" {...props}></Icon>
