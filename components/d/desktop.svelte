<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4uknkf1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x4uknkf1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:desktop" {...props}></Icon>
