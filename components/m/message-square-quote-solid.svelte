<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp8q8eb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp8q8eb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-quote-solid" {...props}></Icon>
