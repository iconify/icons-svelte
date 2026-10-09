<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze5c6ablq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ze5c6ablq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-snow-48" {...props}></Icon>
