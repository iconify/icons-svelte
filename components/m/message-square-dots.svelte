<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4qlrtbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4qlrtbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-square-dots" {...props}></Icon>
