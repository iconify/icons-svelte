<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4g4wxu4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g4g4wxu4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:multi-select" {...props}></Icon>
