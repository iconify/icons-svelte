<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/punybqr-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="punybqr-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:genstat" {...props}></Icon>
