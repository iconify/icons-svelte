<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqkc3tacr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqkc3tacr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-heart-fill" {...props}></Icon>
