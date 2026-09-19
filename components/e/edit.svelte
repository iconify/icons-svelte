<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjhq8mbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rjhq8mbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:edit" {...props}></Icon>
