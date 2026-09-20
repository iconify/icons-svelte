<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhvoj9eul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhvoj9eul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-double-left" {...props}></Icon>
