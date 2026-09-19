<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az40pwb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="az40pwb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:red" {...props}></Icon>
