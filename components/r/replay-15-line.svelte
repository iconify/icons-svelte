<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbre87eyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbre87eyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:replay-15-line" {...props}></Icon>
