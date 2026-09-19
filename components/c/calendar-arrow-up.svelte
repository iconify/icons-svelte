<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kavk_2ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kavk_2ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:calendar-arrow-up" {...props}></Icon>
