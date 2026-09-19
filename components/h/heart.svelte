<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0scw1b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="x0scw1b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:heart" {...props}></Icon>
