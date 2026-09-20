<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msv_7p0iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="msv_7p0iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:link-outline" {...props}></Icon>
