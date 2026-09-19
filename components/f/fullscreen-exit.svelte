<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imt344b4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="imt344b4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:fullscreen-exit" {...props}></Icon>
