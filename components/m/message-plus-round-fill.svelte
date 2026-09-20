<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i45xa5ozt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i45xa5ozt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-plus-round-fill" {...props}></Icon>
