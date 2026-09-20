<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qksq_ubpp.css';
import '../../css/d/d1oljg_vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qksq_ubpp"/><path class="d1oljg_vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:db-ui" {...props}></Icon>
