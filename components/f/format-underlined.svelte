<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngmmfbbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="ngmmfbbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-underlined" {...props}></Icon>
