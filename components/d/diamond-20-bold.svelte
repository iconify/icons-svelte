<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owp_lw21b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="owp_lw21b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:diamond-20-bold" {...props}></Icon>
