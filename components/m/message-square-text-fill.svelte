<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y__pstb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y__pstb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-text-fill" {...props}></Icon>
