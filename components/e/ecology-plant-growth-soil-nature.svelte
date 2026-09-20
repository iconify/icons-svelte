<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv46m4fcb.css';
import '../../css/u/uwe5bpeob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nv46m4fcb"/><path class="uwe5bpeob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:ecology-plant-growth-soil-nature" {...props}></Icon>
