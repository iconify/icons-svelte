<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxk1d8bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxk1d8bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:confetti-solid" {...props}></Icon>
