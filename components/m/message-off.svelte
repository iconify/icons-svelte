<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfghgob2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfghgob2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-off" {...props}></Icon>
