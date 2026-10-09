<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwpdu4b2p.css';
import '../../css/x/xfd9_p-un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cwpdu4b2p"/><path class="xfd9_p-un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ladle-20" {...props}></Icon>
