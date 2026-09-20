<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o11xs_bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o11xs_bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-text-clock" {...props}></Icon>
