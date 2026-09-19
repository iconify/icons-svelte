<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3uhq0alc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":605,"height":680};
const content = `<path class="r3uhq0alc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:bookmark" {...props}></Icon>
