<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0tvro18e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0tvro18e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:reply-line" {...props}></Icon>
