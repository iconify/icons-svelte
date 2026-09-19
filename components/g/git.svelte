<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slvbcs30y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1792};
const content = `<path class="slvbcs30y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:git" {...props}></Icon>
