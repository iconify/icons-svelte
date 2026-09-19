<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8ey5rnuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a8ey5rnuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:boot-volume" {...props}></Icon>
