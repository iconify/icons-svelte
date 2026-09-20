<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km6piqlwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km6piqlwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:funnel" {...props}></Icon>
