<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6fvp9b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6fvp9b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:message-text2-filled" {...props}></Icon>
