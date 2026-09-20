<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f72dkd3ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f72dkd3ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-empty" {...props}></Icon>
