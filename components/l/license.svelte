<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syfbt_k0c.css';
import '../../css/x/xemxelb-k.css';
import '../../css/i/iqucf9blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="syfbt_k0c"/><path class="xemxelb-k"/><path class="iqucf9blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:license" {...props}></Icon>
