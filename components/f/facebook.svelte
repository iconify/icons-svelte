<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le7bgtmct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":224,"height":488};
const content = `<path class="le7bgtmct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:facebook" {...props}></Icon>
