<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_nmcjw-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":410,"height":512};
const content = `<path class="t_nmcjw-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ghostscript" {...props}></Icon>
