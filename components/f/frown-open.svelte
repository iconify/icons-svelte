<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6zc0dp-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a6zc0dp-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:frown-open" {...props}></Icon>
