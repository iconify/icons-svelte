<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/louu8cbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="louu8cbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:concept" {...props}></Icon>
