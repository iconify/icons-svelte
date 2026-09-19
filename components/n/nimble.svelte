<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bng2y_bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bng2y_bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nimble" {...props}></Icon>
