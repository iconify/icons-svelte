<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewbnvrb4j.css';
import '../../css/a/a0qwh727o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ewbnvrb4j"/><path class="a0qwh727o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:image" {...props}></Icon>
