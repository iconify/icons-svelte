<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nivpnqg4j.css';
import '../../css/k/ki4_wwbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nivpnqg4j"/><path class="ki4_wwbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:columns-20-bold" {...props}></Icon>
