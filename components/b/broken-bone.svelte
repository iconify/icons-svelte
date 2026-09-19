<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbfv5kbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbfv5kbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:broken-bone" {...props}></Icon>
