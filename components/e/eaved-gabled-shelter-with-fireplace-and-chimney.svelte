<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_b06wvdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c_b06wvdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-gabled-shelter-with-fireplace-and-chimney" {...props}></Icon>
