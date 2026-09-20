<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w71pim13w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w71pim13w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:message-3-fill" {...props}></Icon>
