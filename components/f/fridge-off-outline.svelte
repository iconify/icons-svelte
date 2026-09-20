<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjo88abed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjo88abed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fridge-off-outline" {...props}></Icon>
