<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt7r-bbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":500};
const content = `<path class="kt7r-bbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pyret" {...props}></Icon>
