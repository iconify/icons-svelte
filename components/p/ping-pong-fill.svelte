<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht5rgbc-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht5rgbc-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ping-pong-fill" {...props}></Icon>
