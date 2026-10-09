<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or3w-hr2p.css';
import '../../css/i/i5nzyoqoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="or3w-hr2p"/><path class="i5nzyoqoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-nacs-20" {...props}></Icon>
