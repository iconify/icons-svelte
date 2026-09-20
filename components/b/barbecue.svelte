<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe581phwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe581phwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:barbecue" {...props}></Icon>
