<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzd5q4bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rzd5q4bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:loader-outline" {...props}></Icon>
