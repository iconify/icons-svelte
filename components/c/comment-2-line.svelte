<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1qx-j91i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1qx-j91i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:comment-2-line" {...props}></Icon>
