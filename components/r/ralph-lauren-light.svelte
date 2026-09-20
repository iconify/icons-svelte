<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7z15dbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":684,"height":1568};
const content = `<path class="u7z15dbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ralph-lauren-light" {...props}></Icon>
