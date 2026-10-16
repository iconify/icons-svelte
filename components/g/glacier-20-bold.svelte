<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2zvukrgy.css';
import '../../css/n/nxke65bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u2zvukrgy"/><path class="nxke65bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:glacier-20-bold" {...props}></Icon>
