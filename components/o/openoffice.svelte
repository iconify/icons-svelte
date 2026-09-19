<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su8pud0wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="su8pud0wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:openoffice" {...props}></Icon>
