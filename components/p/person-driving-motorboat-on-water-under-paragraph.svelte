<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh23lb5bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sh23lb5bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-driving-motorboat-on-water-under-paragraph" {...props}></Icon>
