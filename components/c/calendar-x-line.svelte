<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ton-bn6tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ton-bn6tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-x-line" {...props}></Icon>
