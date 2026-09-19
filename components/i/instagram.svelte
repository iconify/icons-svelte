<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj5j7fs1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tj5j7fs1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:instagram" {...props}></Icon>
