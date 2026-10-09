<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fckik_nux.css';
import '../../css/r/ryvp9vm2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fckik_nux"/><path class="ryvp9vm2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:home-battery-20-bold" {...props}></Icon>
