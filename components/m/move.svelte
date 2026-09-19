<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2twb1bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q2twb1bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:move" {...props}></Icon>
