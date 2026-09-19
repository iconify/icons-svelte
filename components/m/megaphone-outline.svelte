<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8i4wsn-f.css';
import '../../css/g/gucvo3bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m8i4wsn-f"/><path class="gucvo3bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:megaphone-outline" {...props}></Icon>
