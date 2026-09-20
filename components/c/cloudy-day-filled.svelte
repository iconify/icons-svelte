<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5hh4lbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5hh4lbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cloudy-day-filled" {...props}></Icon>
