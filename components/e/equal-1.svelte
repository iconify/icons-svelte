<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3zxih_ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b3zxih_ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:equal-1" {...props}></Icon>
