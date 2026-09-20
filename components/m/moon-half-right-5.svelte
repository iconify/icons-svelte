<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntitz-80y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="ntitz-80y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:moon-half-right-5" {...props}></Icon>
