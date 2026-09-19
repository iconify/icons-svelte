<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu_9h9bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu_9h9bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-square-diff" {...props}></Icon>
