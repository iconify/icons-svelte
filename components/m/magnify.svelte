<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elkmmg68c.css';
import '../../css/y/y3-1k1brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<defs/><path class="elkmmg68c"/><path class="y3-1k1brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:magnify" {...props}></Icon>
