<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i04dlybtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i04dlybtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-top-bold-box" {...props}></Icon>
