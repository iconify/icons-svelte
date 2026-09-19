<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw0f72b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw0f72b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-check-circle" {...props}></Icon>
