<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdpmiccce.css';
import '../../css/i/i6it53bol.css';
import '../../css/i/i1z6z-v6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zdpmiccce"/><path class="i6it53bol"/><path class="i1z6z-v6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ice-melt-48" {...props}></Icon>
