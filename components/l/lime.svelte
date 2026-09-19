<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bma74xb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":405,"height":512};
const content = `<path class="bma74xb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lime" {...props}></Icon>
