<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnygumoma.css';
import '../../css/m/m_7duebkv.css';
import '../../css/h/ht_ws6k_w.css';
import '../../css/g/gkdo6zoja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lnygumoma"/><path class="m_7duebkv"/><path class="ht_ws6k_w"/><path class="gkdo6zoja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:district-cooling-20-bold" {...props}></Icon>
