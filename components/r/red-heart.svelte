<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk5-ttbbm.css';
import '../../css/t/tqz5znvkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="qk5-ttbbm"/><path class="tqz5znvkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:red-heart" {...props}></Icon>
