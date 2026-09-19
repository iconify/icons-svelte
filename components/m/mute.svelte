<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4dg4xj4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f4dg4xj4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:mute" {...props}></Icon>
