<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn-xrwb_q.css';
import '../../css/f/fs5_8vkqb.css';
import '../../css/k/k-njt2b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dn-xrwb_q"/><path class="fs5_8vkqb"/><path class="k-njt2b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:cable-shutoff" {...props}></Icon>
