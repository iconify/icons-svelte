<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulsl_sblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulsl_sblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-smile-3-line" {...props}></Icon>
