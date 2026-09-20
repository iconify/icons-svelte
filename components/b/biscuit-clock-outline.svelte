<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0mqs7bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0mqs7bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:biscuit-clock-outline" {...props}></Icon>
