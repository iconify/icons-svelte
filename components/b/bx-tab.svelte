<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri6cgf8wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri6cgf8wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-tab" {...props}></Icon>
