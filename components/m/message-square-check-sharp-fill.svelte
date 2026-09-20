<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7xhg8b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7xhg8b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-check-sharp-fill" {...props}></Icon>
