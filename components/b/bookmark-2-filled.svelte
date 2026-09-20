<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyabt0bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyabt0bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bookmark-2-filled" {...props}></Icon>
