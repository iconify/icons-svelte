<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od67l8b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="od67l8b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-end-fill-16" {...props}></Icon>
