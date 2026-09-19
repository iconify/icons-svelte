<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axa7ce5ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="axa7ce5ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:forwards" {...props}></Icon>
