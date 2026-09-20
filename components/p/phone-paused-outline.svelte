<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1h25rbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1h25rbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-paused-outline" {...props}></Icon>
