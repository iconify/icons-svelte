<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btuo36bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="btuo36bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:dry-in-the-shade" {...props}></Icon>
