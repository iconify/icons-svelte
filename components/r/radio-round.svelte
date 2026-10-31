<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc362eb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc362eb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:radio-round" {...props}></Icon>
