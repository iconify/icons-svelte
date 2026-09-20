<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhi--6bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yhi--6bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-monitor-heart-beat" {...props}></Icon>
