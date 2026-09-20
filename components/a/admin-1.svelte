<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il0amvbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="il0amvbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:admin-1" {...props}></Icon>
