<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-k-7gbvo.css';
import '../../css/i/ivnpqujhz.css';
import '../../css/s/sps4d_myo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-k-7gbvo"/><path class="ivnpqujhz"/><path class="sps4d_myo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:calendar-grid" {...props}></Icon>
