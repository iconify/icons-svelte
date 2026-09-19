<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6_g96gkl.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="g6_g96gkl"/><circle class="clr-i-badge lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:map-solid-badged" {...props}></Icon>
