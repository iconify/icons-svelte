<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn-xrwb_q.css';
import '../../css/q/qzipmcc8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dn-xrwb_q"/><path class="qzipmcc8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:power-shutoff" {...props}></Icon>
