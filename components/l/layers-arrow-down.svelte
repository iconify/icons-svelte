<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivr_rx2lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivr_rx2lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:layers-arrow-down" {...props}></Icon>
