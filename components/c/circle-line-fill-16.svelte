<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvntw1cis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jvntw1cis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-line-fill-16" {...props}></Icon>
