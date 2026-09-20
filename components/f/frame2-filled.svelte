<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct-dwcbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct-dwcbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:frame2-filled" {...props}></Icon>
