<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1h7nf7fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1h7nf7fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-two" {...props}></Icon>
