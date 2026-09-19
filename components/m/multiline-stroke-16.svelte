<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs423rb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bs423rb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:multiline-stroke-16" {...props}></Icon>
