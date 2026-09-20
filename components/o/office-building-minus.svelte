<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m73j46bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m73j46bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:office-building-minus" {...props}></Icon>
