<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlwuqgbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlwuqgbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:move" {...props}></Icon>
