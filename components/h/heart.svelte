<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzw3sc8yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":37,"height":32};
const content = `<path class="dzw3sc8yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:heart" {...props}></Icon>
