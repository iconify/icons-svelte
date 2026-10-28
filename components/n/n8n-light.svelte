<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxk8m-b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uxk8m-b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:n8n-light" {...props}></Icon>
