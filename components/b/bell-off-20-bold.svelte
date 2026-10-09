<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr2ao-b5d.css';
import '../../css/q/quh-_jkrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pr2ao-b5d"/><path class="quh-_jkrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-off-20-bold" {...props}></Icon>
