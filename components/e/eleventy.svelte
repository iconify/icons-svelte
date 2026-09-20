<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tleff075d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tleff075d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eleventy" {...props}></Icon>
