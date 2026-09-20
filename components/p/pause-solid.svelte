<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl407cb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nl407cb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:pause-solid" {...props}></Icon>
