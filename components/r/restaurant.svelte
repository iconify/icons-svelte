<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-0qsbb3u.css';
import '../../css/r/rbtwur1wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p-0qsbb3u"/><path class="rbtwur1wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:restaurant" {...props}></Icon>
