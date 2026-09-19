<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bllgd364d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bllgd364d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:envelope-open" {...props}></Icon>
