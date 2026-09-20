<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6bbz-whr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6bbz-whr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-check-outline" {...props}></Icon>
