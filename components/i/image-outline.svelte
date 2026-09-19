<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvw4z98pg.css';
import '../../css/l/luchnh4nb.css';
import '../../css/p/p0dnb-b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="wvw4z98pg"/><circle class="luchnh4nb"/><path class="p0dnb-b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:image-outline" {...props}></Icon>
