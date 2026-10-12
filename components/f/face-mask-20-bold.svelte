<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwf-ck3ci.css';
import '../../css/k/kj6dhhbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nwf-ck3ci"/><path class="kj6dhhbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:face-mask-20-bold" {...props}></Icon>
