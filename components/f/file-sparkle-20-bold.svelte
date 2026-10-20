<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iccsyvk3j.css';
import '../../css/i/ipywdhbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iccsyvk3j"/><path class="ipywdhbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-sparkle-20-bold" {...props}></Icon>
