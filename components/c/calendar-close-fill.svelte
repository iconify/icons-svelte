<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twwjopbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twwjopbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:calendar-close-fill" {...props}></Icon>
