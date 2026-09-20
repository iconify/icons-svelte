<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpyb4l3bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wpyb4l3bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:green" {...props}></Icon>
