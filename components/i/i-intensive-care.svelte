<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agqa6qbci.css';
import '../../css/i/ic7d043zq.css';
import '../../css/k/kcldt_bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="agqa6qbci"/><path class="ic7d043zq"/><path class="kcldt_bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-intensive-care" {...props}></Icon>
