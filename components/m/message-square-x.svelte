<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yal5rtb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yal5rtb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-square-x" {...props}></Icon>
