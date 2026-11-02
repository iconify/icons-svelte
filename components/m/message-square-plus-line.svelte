<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt4b9ac1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt4b9ac1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-plus-line" {...props}></Icon>
