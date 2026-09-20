<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9h3vbbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g9h3vbbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-circular-pill-and-capsule-pill" {...props}></Icon>
