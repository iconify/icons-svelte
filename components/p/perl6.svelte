<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gey7z4w5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gey7z4w5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:perl6" {...props}></Icon>
