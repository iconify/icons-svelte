<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3__s4b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t3__s4b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:font-bitmap" {...props}></Icon>
