<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs02q1elk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gs02q1elk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:fast-forward-eight-x" {...props}></Icon>
