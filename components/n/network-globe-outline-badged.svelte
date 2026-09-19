<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gblmqib0s.css';
import '../../css/w/wplx1wc-c.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged gblmqib0s"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged wplx1wc-c"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-3--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:network-globe-outline-badged" {...props}></Icon>
