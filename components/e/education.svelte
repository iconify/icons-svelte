<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su8f1hu3j.css';
import '../../css/r/r6zc52b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="su8f1hu3j"/><path class="r6zc52b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:education" {...props}></Icon>
