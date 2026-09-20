<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwnj5k5sb.css';
import '../../css/b/b7mwlnblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":64};
const content = `<path class="rwnj5k5sb"/><path class="b7mwlnblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ethereum" {...props}></Icon>
