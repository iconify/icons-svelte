<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7f58zkeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a7f58zkeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-oo" {...props}></Icon>
