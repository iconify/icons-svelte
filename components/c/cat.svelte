<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sciuggb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="sciuggb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cat" {...props}></Icon>
