<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-i-v1v3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m-i-v1v3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lefthook" {...props}></Icon>
