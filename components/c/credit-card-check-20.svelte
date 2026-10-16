<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhtd2p4aa.css';
import '../../css/f/flgomrbzx.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mhtd2p4aa"/><path class="flgomrbzx"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:credit-card-check-20" {...props}></Icon>
