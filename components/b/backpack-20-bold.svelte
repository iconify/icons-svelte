<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz3cfsc3k.css';
import '../../css/p/pkhcb0o2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wz3cfsc3k"/><path class="pkhcb0o2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:backpack-20-bold" {...props}></Icon>
