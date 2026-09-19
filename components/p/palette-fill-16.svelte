<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryd9gmy8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ryd9gmy8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:palette-fill-16" {...props}></Icon>
