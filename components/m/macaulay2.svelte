<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xovmwqfiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":388,"height":512};
const content = `<path class="xovmwqfiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:macaulay2" {...props}></Icon>
