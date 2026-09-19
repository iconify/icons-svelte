<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi7958byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gi7958byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:api-blueprint" {...props}></Icon>
