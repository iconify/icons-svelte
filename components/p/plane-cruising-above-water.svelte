<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvyku1b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tvyku1b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-cruising-above-water" {...props}></Icon>
