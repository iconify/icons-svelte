<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb7wkv_1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="eb7wkv_1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:castle-stately-14" {...props}></Icon>
