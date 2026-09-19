<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziyuc4lfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":476,"height":512};
const content = `<path class="ziyuc4lfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:kitchenci" {...props}></Icon>
