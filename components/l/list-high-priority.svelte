<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka_vtlb8j.css';
import '../../css/c/ckzloge-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ka_vtlb8j"/><path class="ckzloge-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:list-high-priority" {...props}></Icon>
