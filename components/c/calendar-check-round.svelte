<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icqdxdhyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icqdxdhyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-check-round" {...props}></Icon>
