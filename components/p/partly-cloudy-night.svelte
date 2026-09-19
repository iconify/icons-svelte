<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5ox36b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p5ox36b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:partly-cloudy-night" {...props}></Icon>
