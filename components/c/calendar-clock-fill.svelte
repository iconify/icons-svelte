<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynhp2xbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ynhp2xbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-clock-fill" {...props}></Icon>
