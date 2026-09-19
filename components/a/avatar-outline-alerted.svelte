<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpbu-db2v.css';
import '../../css/f/fgrccub0d.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--alerted clr-i-outline-path-1--alerted vpbu-db2v"/><path class="clr-i-outline--alerted clr-i-outline-path-2--alerted fgrccub0d"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-3--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:avatar-outline-alerted" {...props}></Icon>
