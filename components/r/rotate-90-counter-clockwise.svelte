<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q75nhsbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q75nhsbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:rotate-90-counter-clockwise" {...props}></Icon>
