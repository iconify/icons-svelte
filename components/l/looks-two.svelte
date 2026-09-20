<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwulq_bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwulq_bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:looks-two" {...props}></Icon>
