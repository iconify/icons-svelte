<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zngyyzlhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zngyyzlhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-circle-fill-16" {...props}></Icon>
