<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6zsw8m6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r6zsw8m6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:google-ad-outline" {...props}></Icon>
