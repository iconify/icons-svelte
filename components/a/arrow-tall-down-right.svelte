<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rliur8haw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rliur8haw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:arrow-tall-down-right" {...props}></Icon>
