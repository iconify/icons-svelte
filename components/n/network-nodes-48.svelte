<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4caingdq.css';
import '../../css/s/sy8emvbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e4caingdq"/><path class="sy8emvbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:network-nodes-48" {...props}></Icon>
