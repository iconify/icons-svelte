<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma2wh1fer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma2wh1fer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-dots" {...props}></Icon>
