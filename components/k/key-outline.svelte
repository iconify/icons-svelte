<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brn89rbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="brn89rbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:key-outline" {...props}></Icon>
