<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-q-p1bwi.css';
import '../../css/t/tld7w6b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m-q-p1bwi"/><path class="tld7w6b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badge-check-20-bold" {...props}></Icon>
