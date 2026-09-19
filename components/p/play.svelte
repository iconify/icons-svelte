<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpky_m6mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rpky_m6mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:play" {...props}></Icon>
