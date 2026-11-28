<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thz9ypb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thz9ypb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-code-solid" {...props}></Icon>
