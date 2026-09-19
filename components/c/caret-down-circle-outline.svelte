<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crkvjda8n.css';
import '../../css/l/lsg5j7ibl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="crkvjda8n"/><path class="lsg5j7ibl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:caret-down-circle-outline" {...props}></Icon>
