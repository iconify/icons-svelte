<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecdco1b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ecdco1b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:adobe" {...props}></Icon>
