<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ked3dlbrv.css';
import '../../css/q/qpoa4dbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ked3dlbrv"/><path class="qpoa4dbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:munin" {...props}></Icon>
