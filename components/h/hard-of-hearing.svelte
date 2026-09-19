<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mls71jonh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="mls71jonh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hard-of-hearing" {...props}></Icon>
