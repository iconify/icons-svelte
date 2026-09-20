<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur9f9shlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ur9f9shlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:height-restrictor" {...props}></Icon>
