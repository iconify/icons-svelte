<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4w0f9o9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4w0f9o9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chimney-1-filled" {...props}></Icon>
