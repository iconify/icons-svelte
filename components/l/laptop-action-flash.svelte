<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk95g98tl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nk95g98tl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:laptop-action-flash" {...props}></Icon>
